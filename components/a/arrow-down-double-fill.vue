<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7869lbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7869lbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-double-fill" /></template>
