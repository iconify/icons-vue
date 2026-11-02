<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvo71abpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvo71abpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-2-line" /></template>
