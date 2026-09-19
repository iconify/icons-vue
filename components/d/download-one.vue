<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf28uwb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vf28uwb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:download-one" /></template>
