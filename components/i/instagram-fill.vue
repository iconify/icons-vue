<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj4yr04wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj4yr04wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:instagram-fill" /></template>
