<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r82s_ibsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r82s_ibsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cart-plus" /></template>
