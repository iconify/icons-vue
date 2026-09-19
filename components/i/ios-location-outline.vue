<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs68a2a3q.css';
import '../../css/c/cb56blb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gs68a2a3q"/><path class="cb56blb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-location-outline" /></template>
