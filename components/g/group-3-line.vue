<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgb_9abwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgb_9abwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-3-line" /></template>
