<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcl98g9-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mcl98g9-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-with-exclamation-point" /></template>
