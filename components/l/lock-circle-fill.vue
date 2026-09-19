<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm4lx_ftr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jm4lx_ftr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-circle-fill" /></template>
