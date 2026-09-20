<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwtzf7nop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwtzf7nop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-transfer-fill" /></template>
