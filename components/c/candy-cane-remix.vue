<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uktlwkbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uktlwkbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:candy-cane-remix" /></template>
