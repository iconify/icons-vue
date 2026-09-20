<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw2zl7-aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rw2zl7-aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:guardian-plex" /></template>
