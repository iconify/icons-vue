<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1uj_r0_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1uj_r0_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:line-cap-flat" /></template>
