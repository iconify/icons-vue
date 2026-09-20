<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urgydkccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="urgydkccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:amusement-park" /></template>
