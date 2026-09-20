<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ec4ib1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1ec4ib1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agentgateway-dark" /></template>
