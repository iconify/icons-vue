<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu0lojbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0lojbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-minus-2-line" /></template>
