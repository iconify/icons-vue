<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8gcewbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8gcewbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:antora-light" /></template>
