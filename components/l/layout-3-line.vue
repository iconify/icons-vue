<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoji1cctt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoji1cctt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-3-line" /></template>
