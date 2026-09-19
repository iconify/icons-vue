<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q84q2v45v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q84q2v45v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-hourglass" /></template>
