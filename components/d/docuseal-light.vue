<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2ee7r-6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2ee7r-6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docuseal-light" /></template>
