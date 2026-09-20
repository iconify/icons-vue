<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5jbg97bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g5jbg97bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grunt" /></template>
