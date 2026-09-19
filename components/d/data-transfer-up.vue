<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9r8cbbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9r8cbbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:data-transfer-up" /></template>
