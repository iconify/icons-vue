<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1q7olbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1q7olbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:codepen" /></template>
