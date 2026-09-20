<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic-zq4-uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ic-zq4-uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grok-light" /></template>
