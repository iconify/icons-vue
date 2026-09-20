<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxjq2obsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yxjq2obsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-file-delete-file-common-delete" /></template>
