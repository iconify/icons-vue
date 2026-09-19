<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1283djp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in1283djp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-tennisball-outline" /></template>
