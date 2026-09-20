<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvtw_wblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvtw_wblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:debian" /></template>
