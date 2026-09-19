<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdi89ozbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kdi89ozbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arrows-horz" /></template>
