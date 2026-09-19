<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoy6yv3cj.css';
import '../../css/y/yef4huqia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xoy6yv3cj"/><path class="yef4huqia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackfolder" /></template>
