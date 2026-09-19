<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7_ev5eiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7_ev5eiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-thin-down" /></template>
