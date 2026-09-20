<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t54_tnbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t54_tnbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dental-fill" /></template>
