<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynqrycc5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ynqrycc5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:level-up-alt" /></template>
