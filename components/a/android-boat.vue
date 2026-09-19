<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol18m9l3x.css';
import '../../css/r/rhyynac5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ol18m9l3x"/><path class="rhyynac5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-boat" /></template>
