<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_q6c7r9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="g_q6c7r9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:keyboard-f" /></template>
