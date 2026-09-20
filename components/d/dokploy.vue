<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yequ1mb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yequ1mb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dokploy" /></template>
