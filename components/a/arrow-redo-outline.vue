<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5i3hibgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5i3hibgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-redo-outline" /></template>
