<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_rq9mb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_rq9mb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:d" /></template>
