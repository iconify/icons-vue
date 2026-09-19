<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-yolg93x.css';
import '../../css/x/x_6no5bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-yolg93x"/><path class="x_6no5bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:door-open" /></template>
