<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkq99-j3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="rkq99-j3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:capsules" /></template>
