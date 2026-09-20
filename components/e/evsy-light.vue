<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbpz_ob3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbpz_ob3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:evsy-light" /></template>
