<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hswj1gb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hswj1gb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-horizontal-2-fill" /></template>
