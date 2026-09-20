<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ab5ac2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f8ab5ac2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:magnet" /></template>
