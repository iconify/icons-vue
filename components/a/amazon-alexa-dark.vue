<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do-ojo0gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="do-ojo0gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-alexa-dark" /></template>
