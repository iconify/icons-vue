<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_uzxcyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n1_uzxcyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bow-tie-solid" /></template>
