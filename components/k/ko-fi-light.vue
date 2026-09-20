<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scixahb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scixahb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ko-fi-light" /></template>
