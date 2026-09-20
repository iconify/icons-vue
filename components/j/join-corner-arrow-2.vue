<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__bsmjwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q__bsmjwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:join-corner-arrow-2" /></template>
