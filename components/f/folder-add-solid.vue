<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwttnzbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nwttnzbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:folder-add-solid" /></template>
