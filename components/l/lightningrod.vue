<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb-hsiek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rnb-hsiek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lightningrod" /></template>
