<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj3mm2bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj3mm2bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-folder-outline" /></template>
