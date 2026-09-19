<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_p34886l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_p34886l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hand-right" /></template>
