<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hclyphmkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hclyphmkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:first-aid-kit-fill" /></template>
