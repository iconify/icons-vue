<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce1v0cccs.css';
import '../../css/x/xnqtkuy1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ce1v0cccs"/><path class="xnqtkuy1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-learning" /></template>
