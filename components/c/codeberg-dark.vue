<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_oyv7tku.css';
import '../../css/m/m36y1-ioy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_oyv7tku"/><path class="m36y1-ioy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codeberg-dark" /></template>
