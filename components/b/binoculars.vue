<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln1jp2beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln1jp2beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:binoculars" /></template>
