<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox6ijkv2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ox6ijkv2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lexware-light" /></template>
