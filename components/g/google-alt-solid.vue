<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyr2sybkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyr2sybkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-alt-solid" /></template>
