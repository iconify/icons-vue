<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8z9hyvrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8z9hyvrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:bluesky" /></template>
