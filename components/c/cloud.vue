<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oizp8mura.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oizp8mura"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:cloud" /></template>
