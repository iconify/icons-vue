<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-78cfw_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c-78cfw_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:block-2-flat" /></template>
