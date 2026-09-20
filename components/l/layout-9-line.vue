<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llcarc34f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llcarc34f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-9-line" /></template>
