<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5ovopb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="z5ovopb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:firefox" /></template>
