<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghx_bmbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghx_bmbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loglynx" /></template>
