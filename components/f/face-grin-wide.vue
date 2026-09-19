<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6obxeb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6obxeb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-wide" /></template>
