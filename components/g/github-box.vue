<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aodq9y6zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aodq9y6zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:github-box" /></template>
