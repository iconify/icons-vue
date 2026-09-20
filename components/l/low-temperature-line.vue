<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlrh-ubaa.css';
import '../../css/u/u13yqv0ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlrh-ubaa"/><path class="u13yqv0ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:low-temperature-line" /></template>
