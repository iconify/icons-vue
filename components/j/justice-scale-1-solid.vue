<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-cuw3bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-cuw3bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:justice-scale-1-solid" /></template>
