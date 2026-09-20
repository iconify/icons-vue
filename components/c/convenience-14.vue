<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym5a20iat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ym5a20iat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:convenience-14" /></template>
