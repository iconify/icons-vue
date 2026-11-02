<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go0e-obdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go0e-obdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-3-line" /></template>
