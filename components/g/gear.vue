<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptv7zfbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ptv7zfbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gear" /></template>
