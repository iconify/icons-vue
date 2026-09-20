<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4f9vybma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s4f9vybma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-low-1-solid" /></template>
