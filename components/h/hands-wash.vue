<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq0-i1bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fq0-i1bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hands-wash" /></template>
