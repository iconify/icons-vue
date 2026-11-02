<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpx2bv8xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx2bv8xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-4-line" /></template>
