<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg90zxbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg90zxbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-down-wide-narrow-line" /></template>
