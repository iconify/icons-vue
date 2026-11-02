<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k59_d8b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k59_d8b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hammer-2-fill" /></template>
