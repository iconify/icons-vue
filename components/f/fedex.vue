<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3zyzcc0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3zyzcc0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fedex" /></template>
