<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhun8vz6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="rhun8vz6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grip-vertical" /></template>
