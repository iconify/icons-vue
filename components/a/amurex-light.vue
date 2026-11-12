<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_pbdbb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_pbdbb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amurex-light" /></template>
