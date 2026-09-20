<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juqc6xgep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juqc6xgep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:key-2-line" /></template>
