<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmpz27ccw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmpz27ccw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-long-outline-24px" /></template>
