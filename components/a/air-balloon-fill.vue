<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a18-ftbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a18-ftbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-balloon-fill" /></template>
