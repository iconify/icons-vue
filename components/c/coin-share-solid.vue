<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0efds0oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0efds0oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:coin-share-solid" /></template>
