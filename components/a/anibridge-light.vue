<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swdvhieyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swdvhieyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anibridge-light" /></template>
