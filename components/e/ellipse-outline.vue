<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ouhtb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q3ouhtb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ellipse-outline" /></template>
