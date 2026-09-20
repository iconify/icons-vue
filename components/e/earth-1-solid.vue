<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiy_nybza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fiy_nybza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:earth-1-solid" /></template>
