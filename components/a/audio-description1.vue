<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt-2qd5ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt-2qd5ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:audio-description1" /></template>
