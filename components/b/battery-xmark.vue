<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh7uwob5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fh7uwob5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-xmark" /></template>
