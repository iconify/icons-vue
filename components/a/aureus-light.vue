<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwucx9qju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dwucx9qju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aureus-light" /></template>
