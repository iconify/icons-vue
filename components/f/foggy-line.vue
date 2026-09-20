<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2d12ibxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2d12ibxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:foggy-line" /></template>
