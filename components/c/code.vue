<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zguwfcbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":472};
const content = `<path class="zguwfcbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:code" /></template>
