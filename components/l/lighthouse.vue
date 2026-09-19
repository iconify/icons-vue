<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvtfu18_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvtfu18_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lighthouse" /></template>
