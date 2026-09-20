<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsi-k6tgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zsi-k6tgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crunchyroll-light" /></template>
