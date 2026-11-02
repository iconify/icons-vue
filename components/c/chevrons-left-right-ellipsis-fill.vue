<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc78igbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc78igbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-left-right-ellipsis-fill" /></template>
