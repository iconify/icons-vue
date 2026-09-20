<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib7ibmduz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ib7ibmduz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hd-screen-solid" /></template>
