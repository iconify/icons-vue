<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4-vycwzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4-vycwzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:film-line" /></template>
