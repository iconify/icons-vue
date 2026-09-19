<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr1sutbfj.css';
import '../../css/l/ll09ir12a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vr1sutbfj"/><path class="ll09ir12a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fitness" /></template>
