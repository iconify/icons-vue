<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_59qsblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g_59qsblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-16-solid" /></template>
