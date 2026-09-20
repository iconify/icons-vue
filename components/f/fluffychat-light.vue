<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_np0pzjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_np0pzjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluffychat-light" /></template>
