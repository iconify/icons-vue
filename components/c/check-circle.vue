<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5oymtkop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5oymtkop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:check-circle" /></template>
