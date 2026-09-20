<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc5trhbqj.css';
import '../../css/p/p6ca8ub5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dc5trhbqj"/><path class="p6ca8ub5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:akkoma" /></template>
