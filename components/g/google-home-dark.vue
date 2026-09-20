<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjgsc_5dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kjgsc_5dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-home-dark" /></template>
