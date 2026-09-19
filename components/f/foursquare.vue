<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwfny99kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":456};
const content = `<path class="rwfny99kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:foursquare" /></template>
