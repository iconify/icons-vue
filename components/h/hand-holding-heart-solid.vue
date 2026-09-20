<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7elhyu2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z7elhyu2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-holding-heart-solid" /></template>
