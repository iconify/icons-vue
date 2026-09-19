<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppv_c6bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ppv_c6bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-lock" /></template>
