<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzzvbkgsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="lzzvbkgsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angle-down" /></template>
