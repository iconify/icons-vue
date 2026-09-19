<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxrpz4blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jxrpz4blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-medical-alt" /></template>
