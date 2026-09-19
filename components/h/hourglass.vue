<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eph_-e7pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="eph_-e7pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hourglass" /></template>
