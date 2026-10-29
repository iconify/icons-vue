<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4s8tgwzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4s8tgwzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-input-solid" /></template>
