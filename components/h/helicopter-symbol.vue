<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbnu52b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zbnu52b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:helicopter-symbol" /></template>
