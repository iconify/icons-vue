<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-33augld.css';
import '../../css/b/bxfwu8b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-33augld"/><path class="bxfwu8b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-planet" /></template>
