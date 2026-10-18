<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2kqa_qdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2kqa_qdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-5" /></template>
