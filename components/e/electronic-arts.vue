<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq-yft7qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2225,"height":399};
const content = `<path clip-rule="evenodd" class="zq-yft7qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:electronic-arts" /></template>
