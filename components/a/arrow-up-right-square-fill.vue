<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwzbv5bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mwzbv5bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-right-square-fill" /></template>
