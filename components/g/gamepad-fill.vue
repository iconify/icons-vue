<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciyf57kyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciyf57kyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gamepad-fill" /></template>
