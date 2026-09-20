<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycmvceb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ycmvceb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hypermind-light" /></template>
