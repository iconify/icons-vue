<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn9zjzj1e.css';
import '../../css/m/m52u-s6oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yn9zjzj1e"/><path class="m52u-s6oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hammer-editor" /></template>
