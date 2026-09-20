<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcinb9mms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mcinb9mms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lift-disability-solid" /></template>
