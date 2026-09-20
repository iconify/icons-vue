<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szc-0q-at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szc-0q-at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:backward" /></template>
