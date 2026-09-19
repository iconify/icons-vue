<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_nmcjw-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":410,"height":512};
const content = `<path class="t_nmcjw-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ghostscript" /></template>
