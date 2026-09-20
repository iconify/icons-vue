<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfkb007lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfkb007lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:fruit-banana-bold" /></template>
