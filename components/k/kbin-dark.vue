<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qove3cb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qove3cb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kbin-dark" /></template>
