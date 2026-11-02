<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_c4e9r8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_c4e9r8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barrel-2-line" /></template>
