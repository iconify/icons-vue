<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ydx-euj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o5ydx-euj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-2-solid" /></template>
