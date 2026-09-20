<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa54thbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fa54thbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-dark" /></template>
