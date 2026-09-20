<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhizt-1jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rhizt-1jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-dollar-solid" /></template>
