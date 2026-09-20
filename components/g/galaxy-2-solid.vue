<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk58jbbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xk58jbbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:galaxy-2-solid" /></template>
