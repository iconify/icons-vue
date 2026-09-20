<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ias7glzgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ias7glzgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:fork-spoon-flat" /></template>
