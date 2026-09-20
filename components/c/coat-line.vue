<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chk0begud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chk0begud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coat-line" /></template>
