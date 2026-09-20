<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbk3imekb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbk3imekb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graphhopper-dark" /></template>
