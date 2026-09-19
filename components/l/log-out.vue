<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixx1zab_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixx1zab_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:log-out" /></template>
