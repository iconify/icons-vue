<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la7tnabna.css';
import '../../css/w/w7blx8bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="la7tnabna"/><path class="w7blx8bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:initiative-project-management-dark" /></template>
