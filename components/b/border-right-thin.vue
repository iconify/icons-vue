<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk63w7-dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jk63w7-dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-right-thin" /></template>
