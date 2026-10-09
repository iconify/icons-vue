<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4lrodbjn.css';
import '../../css/s/s3ntjw07u.css';
import '../../css/p/pkgh68sab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l4lrodbjn"/><path class="s3ntjw07u"/><path class="pkgh68sab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:district-heating-48" /></template>
