<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc1dn3bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc1dn3bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:left-arrow-circle" /></template>
