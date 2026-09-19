<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu1t95b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nu1t95b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hulu" /></template>
