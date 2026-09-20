<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke_ynsmfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ke_ynsmfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:layer-group" /></template>
