<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtz0htvld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dtz0htvld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:file-remove-alternate-solid" /></template>
