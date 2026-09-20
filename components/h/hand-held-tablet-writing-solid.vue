<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifrmrz2jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ifrmrz2jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hand-held-tablet-writing-solid" /></template>
