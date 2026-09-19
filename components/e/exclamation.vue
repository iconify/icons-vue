<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zryyp6ntt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="zryyp6ntt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:exclamation" /></template>
