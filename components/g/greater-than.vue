<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkxrnlbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hkxrnlbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:greater-than" /></template>
