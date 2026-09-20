<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/semirj3sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="semirj3sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gameyfin-dark" /></template>
