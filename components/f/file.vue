<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py8bx-zrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py8bx-zrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file" /></template>
