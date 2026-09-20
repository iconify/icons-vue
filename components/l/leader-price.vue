<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfo6gbb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfo6gbb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:leader-price" /></template>
