<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjafd7blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sjafd7blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:ampersand-flat" /></template>
