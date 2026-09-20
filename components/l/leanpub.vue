<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc19e372j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mc19e372j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:leanpub" /></template>
