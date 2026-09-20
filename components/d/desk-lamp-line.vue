<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqowdxbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqowdxbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:desk-lamp-line" /></template>
