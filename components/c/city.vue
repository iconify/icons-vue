<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqc13dx2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqc13dx2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:city" /></template>
