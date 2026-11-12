<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_20abpwf.css';
import '../../css/m/m01ydll8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n_20abpwf"/><path class="m01ydll8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-locker-light" /></template>
