<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9s3m40bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a9s3m40bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-tray-1-solid" /></template>
