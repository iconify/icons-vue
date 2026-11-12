<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf0iphdax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf0iphdax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kaunta-light" /></template>
