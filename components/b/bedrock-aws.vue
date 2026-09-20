<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a54otobbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a54otobbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bedrock-aws" /></template>
