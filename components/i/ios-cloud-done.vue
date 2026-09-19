<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcrw8i3lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcrw8i3lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-done" /></template>
