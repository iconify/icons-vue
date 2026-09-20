<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g16uogwjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g16uogwjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-warning-solid" /></template>
