<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr0yhbb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr0yhbb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-slash-24" /></template>
