<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se4p66b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se4p66b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-pile-fill" /></template>
