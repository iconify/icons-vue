<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iddnc4agt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iddnc4agt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ersatztv-light" /></template>
