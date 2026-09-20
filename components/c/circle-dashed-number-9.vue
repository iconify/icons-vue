<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/homhz8bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="homhz8bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-number-9" /></template>
