<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7jcl1b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e7jcl1b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-waypoint-dark" /></template>
