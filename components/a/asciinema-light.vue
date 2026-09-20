<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa--8wbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa--8wbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asciinema-light" /></template>
