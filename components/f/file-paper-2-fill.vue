<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xts0dhppt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xts0dhppt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-paper-2-fill" /></template>
