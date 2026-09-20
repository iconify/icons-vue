<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_zalb5pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_zalb5pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-light" /></template>
