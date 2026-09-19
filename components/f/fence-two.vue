<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8s4zn2iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n8s4zn2iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:fence-two" /></template>
