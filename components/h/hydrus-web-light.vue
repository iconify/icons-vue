<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfh4nmb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfh4nmb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hydrus-web-light" /></template>
