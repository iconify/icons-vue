<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj3mau4il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj3mau4il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-close-line" /></template>
