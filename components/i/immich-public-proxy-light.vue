<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecff8-bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ecff8-bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-public-proxy-light" /></template>
