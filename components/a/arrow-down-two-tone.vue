<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz2kdjbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz2kdjbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-two-tone" /></template>
