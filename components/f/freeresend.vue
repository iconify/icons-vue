<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff5t4wldt.css';
import '../../css/n/ng743gb9u.css';
import '../../css/x/x8brv2t3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff5t4wldt"/><path class="ng743gb9u"/><path class="x8brv2t3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeresend" /></template>
