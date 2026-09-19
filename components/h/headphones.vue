<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf6js5bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zf6js5bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:headphones" /></template>
