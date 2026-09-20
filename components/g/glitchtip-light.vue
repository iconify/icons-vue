<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegwdd90q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oegwdd90q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glitchtip-light" /></template>
