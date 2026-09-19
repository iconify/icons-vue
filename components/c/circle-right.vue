<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6o644bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6o644bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-right" /></template>
