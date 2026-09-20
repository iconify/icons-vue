<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8plw6brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e8plw6brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-bend-left-down-2-solid" /></template>
