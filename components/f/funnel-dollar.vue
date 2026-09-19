<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f--7-bb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f--7-bb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:funnel-dollar" /></template>
