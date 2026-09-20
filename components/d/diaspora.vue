<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wln7cnp3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wln7cnp3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:diaspora" /></template>
