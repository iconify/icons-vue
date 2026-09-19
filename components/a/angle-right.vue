<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk86-bv6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="hk86-bv6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angle-right" /></template>
