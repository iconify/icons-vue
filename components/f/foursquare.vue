<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4gg6fwiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j4gg6fwiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:foursquare" /></template>
