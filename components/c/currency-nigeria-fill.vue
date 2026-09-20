<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd57n2brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd57n2brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-nigeria-fill" /></template>
