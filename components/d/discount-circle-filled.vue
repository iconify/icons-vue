<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgnqlyb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgnqlyb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:discount-circle-filled" /></template>
