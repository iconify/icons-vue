<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpmq7pbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpmq7pbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cooler-control-light" /></template>
