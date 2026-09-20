<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6-fjpx-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i6-fjpx-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-tv" /></template>
