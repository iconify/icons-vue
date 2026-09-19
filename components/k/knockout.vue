<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn8m8huco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zn8m8huco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:knockout" /></template>
