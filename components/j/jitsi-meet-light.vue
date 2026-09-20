<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt367vgwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zt367vgwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jitsi-meet-light" /></template>
