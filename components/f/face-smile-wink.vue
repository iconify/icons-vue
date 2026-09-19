<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rndt-obnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rndt-obnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-smile-wink" /></template>
