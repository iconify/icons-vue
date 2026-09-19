<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2oa1ubnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2oa1ubnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-play-outline" /></template>
