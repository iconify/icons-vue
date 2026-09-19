<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcw82nfcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcw82nfcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:comment-dots" /></template>
