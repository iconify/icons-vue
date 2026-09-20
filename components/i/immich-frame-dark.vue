<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr6vxmbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qr6vxmbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-frame-dark" /></template>
