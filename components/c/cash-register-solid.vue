<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxx9ecuqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxx9ecuqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cash-register-solid" /></template>
