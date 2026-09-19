<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt4r-82jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xt4r-82jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-right-box-sharp" /></template>
