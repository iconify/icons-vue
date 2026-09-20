<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyj-u0bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyj-u0bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cookie-man-fill" /></template>
