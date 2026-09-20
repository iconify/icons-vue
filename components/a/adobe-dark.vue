<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi7gwbcja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yi7gwbcja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-dark" /></template>
