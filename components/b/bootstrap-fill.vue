<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtdrdb__o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtdrdb__o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bootstrap-fill" /></template>
