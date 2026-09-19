<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-otfqkuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-otfqkuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:baguette" /></template>
