<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz--5rbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz--5rbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bedrock-aws" /></template>
