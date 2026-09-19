<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-8nonb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":356,"height":512};
const content = `<path class="r-8nonb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:build-boot" /></template>
