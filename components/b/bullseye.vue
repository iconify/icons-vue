<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_f70lduw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_f70lduw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bullseye" /></template>
