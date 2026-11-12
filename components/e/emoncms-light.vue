<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd4o_acha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bd4o_acha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emoncms-light" /></template>
