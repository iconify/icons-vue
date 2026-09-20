<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc53ejohh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc53ejohh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dtx" /></template>
