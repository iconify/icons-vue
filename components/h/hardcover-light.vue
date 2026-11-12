<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epx4oac-v.css';
import '../../css/k/k4v90z5go.css';
import '../../css/h/hv1gm7eyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epx4oac-v"/><path class="k4v90z5go"/><path class="hv1gm7eyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hardcover-light" /></template>
