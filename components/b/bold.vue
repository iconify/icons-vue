<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs17w9b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hs17w9b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bold" /></template>
