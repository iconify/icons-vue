<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjh43p2th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjh43p2th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:habitat-social-dark" /></template>
