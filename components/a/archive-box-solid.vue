<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azo4x4paw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="azo4x4paw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:archive-box-solid" /></template>
