<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3w0cnbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g3w0cnbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cube-box-fill" /></template>
