<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xop-chz3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xop-chz3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-japanese-yen" /></template>
