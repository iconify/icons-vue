<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilgom-ekr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilgom-ekr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cancer-line" /></template>
