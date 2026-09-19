<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg5d1vbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jg5d1vbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-circle-check" /></template>
