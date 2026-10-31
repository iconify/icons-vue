<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_qurr6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_qurr6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-close-round" /></template>
