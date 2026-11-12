<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue2g5nbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue2g5nbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jitsi-meet-light" /></template>
