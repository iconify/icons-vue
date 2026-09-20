<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-zcbiwap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-zcbiwap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-1-fill" /></template>
