<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmyfz1bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tmyfz1bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubecraft-light" /></template>
