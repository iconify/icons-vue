<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3hcn1bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3hcn1bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:at" /></template>
