<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc_mv5j_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc_mv5j_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arch-linux" /></template>
