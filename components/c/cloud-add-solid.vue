<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv-o7vb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lv-o7vb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-add-solid" /></template>
