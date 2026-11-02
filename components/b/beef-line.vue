<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvr5zlrke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvr5zlrke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beef-line" /></template>
