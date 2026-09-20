<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0uk8wbky.css';
import '../../css/a/acmcm-bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0uk8wbky"/><path class="acmcm-bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-tag-manager-dark" /></template>
