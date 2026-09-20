<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg9unybms.css';
import '../../css/f/fv0y09b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vg9unybms"/><path class="fv0y09b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chili3d" /></template>
