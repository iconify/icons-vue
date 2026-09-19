<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r50l1jf5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r50l1jf5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cloud-circle" /></template>
