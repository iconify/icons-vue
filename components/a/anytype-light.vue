<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1r5bbcod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1r5bbcod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anytype-light" /></template>
