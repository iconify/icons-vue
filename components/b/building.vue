<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_am6mbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f_am6mbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:building" /></template>
