<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6m0izbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6m0izbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grass-io" /></template>
