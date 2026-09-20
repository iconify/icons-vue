<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4b2zt-qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r4b2zt-qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-folder-add-add-folder-plus" /></template>
