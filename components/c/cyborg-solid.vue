<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-0x3bbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-0x3bbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cyborg-solid" /></template>
