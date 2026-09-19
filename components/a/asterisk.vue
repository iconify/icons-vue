<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs7_jfbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vs7_jfbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:asterisk" /></template>
