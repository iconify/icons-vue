<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nly739b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nly739b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coin-3-fill" /></template>
