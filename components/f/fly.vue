<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfsrg4brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sfsrg4brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fly" /></template>
