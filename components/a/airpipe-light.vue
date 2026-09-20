<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azmjybbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azmjybbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airpipe-light" /></template>
