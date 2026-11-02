<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asglhu-pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asglhu-pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-2-fill" /></template>
