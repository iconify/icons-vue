<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekixpy_qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekixpy_qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:donate" /></template>
