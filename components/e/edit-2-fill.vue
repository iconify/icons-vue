<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqod50btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqod50btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-2-fill" /></template>
