<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu51u7m2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vu51u7m2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-mouse" /></template>
