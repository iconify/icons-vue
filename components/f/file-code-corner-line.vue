<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr2zs_bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr2zs_bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-code-corner-line" /></template>
