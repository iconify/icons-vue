<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diuxkcx9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diuxkcx9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-paper-2-line" /></template>
