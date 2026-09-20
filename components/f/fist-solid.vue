<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8xfq6idc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c8xfq6idc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fist-solid" /></template>
