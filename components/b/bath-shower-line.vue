<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku0o0cc0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0o0cc0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bath-shower-line" /></template>
