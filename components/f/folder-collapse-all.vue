<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewdzdgb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewdzdgb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-collapse-all" /></template>
