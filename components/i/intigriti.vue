<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj586r4go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj586r4go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:intigriti" /></template>
