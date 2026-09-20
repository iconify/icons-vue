<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_3e1wbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e_3e1wbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:file-delete-alternate-solid" /></template>
