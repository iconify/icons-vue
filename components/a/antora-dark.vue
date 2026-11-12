<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp5s9ylyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp5s9ylyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:antora-dark" /></template>
