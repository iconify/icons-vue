<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnflv5bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tnflv5bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:download" /></template>
