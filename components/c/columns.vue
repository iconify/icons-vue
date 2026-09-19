<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypcd6hb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypcd6hb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:columns" /></template>
