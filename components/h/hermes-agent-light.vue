<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da8y-n0pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="da8y-n0pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hermes-agent-light" /></template>
