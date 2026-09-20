<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwo9clbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwo9clbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:coin-line" /></template>
