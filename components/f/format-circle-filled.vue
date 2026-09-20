<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcqr42bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcqr42bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:format-circle-filled" /></template>
