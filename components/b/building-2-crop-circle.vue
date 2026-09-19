<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd8gkybdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pd8gkybdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:building-2-crop-circle" /></template>
