<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7lovacep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="n7lovacep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:i" /></template>
