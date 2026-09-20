<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4ovr_bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4ovr_bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gitconnected" /></template>
