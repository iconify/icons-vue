<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgq8g5bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgq8g5bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-back-2-fill" /></template>
