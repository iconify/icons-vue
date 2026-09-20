<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyz20i6jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tyz20i6jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-arrow-decrease-solid" /></template>
