<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9tegybcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9tegybcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:id-card-alt" /></template>
