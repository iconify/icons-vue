<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppzj34bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ppzj34bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-up-lock" /></template>
