<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpj1v4jjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpj1v4jjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:foot-line" /></template>
