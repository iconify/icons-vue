<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifp5jlboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifp5jlboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:american-express-line" /></template>
