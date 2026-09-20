<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyi3bcceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyi3bcceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-top-fill" /></template>
