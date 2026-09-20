<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz8y4okya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rz8y4okya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-waypoint" /></template>
