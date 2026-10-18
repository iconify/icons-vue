<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv17pwgmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv17pwgmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-minus" /></template>
