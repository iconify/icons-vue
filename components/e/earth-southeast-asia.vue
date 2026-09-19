<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b78-uobgs.css';
import '../../css/e/eqms1ckur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b78-uobgs"/><path class="eqms1ckur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth-southeast-asia" /></template>
