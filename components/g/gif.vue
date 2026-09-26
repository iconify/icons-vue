<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iralbodoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iralbodoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:gif" /></template>
