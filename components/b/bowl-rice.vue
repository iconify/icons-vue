<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfw5puwlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfw5puwlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bowl-rice" /></template>
