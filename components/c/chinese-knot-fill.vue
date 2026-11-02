<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvmku2bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvmku2bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chinese-knot-fill" /></template>
