<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck5xyu9ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck5xyu9ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-3-fill" /></template>
