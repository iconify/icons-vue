<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2fefzbda.css';
import '../../css/t/ttor7fbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2fefzbda"/><path class="ttor7fbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:foss-events" /></template>
