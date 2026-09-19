<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxwm93b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gxwm93b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:document-remove" /></template>
