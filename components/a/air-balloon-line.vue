<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pejmsfqng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pejmsfqng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-balloon-line" /></template>
