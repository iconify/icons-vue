<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sozdzcb0a.css';
import '../../css/o/om5h7lb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path class="om5h7lb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-candlestick-filled" /></template>
