<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1dkfib5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1dkfib5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera2-filled" /></template>
