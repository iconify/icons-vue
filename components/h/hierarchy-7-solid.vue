<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_eqeohls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_eqeohls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-7-solid" /></template>
