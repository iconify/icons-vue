<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsayo-blv.css';
import '../../css/c/c7ebenbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wsayo-blv"/><path class="c7ebenbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flarum-light" /></template>
