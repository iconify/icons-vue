<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6xg3bb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j6xg3bb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:flat-brush" /></template>
