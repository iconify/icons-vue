<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdxb9k3ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdxb9k3ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-fill" /></template>
