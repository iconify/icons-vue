<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_guwunvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c_guwunvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:icloud" /></template>
