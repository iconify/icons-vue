<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or4mibcim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="or4mibcim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:goaccess-dark" /></template>
