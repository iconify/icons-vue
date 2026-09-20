<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2qcexb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2qcexb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeipa-light" /></template>
