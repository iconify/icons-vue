<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn__pccuq.css';
import '../../css/v/v9fq-0n-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn__pccuq"/><path class="v9fq-0n-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-5-line" /></template>
