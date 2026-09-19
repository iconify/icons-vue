<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxdlb5s3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxdlb5s3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:1c" /></template>
