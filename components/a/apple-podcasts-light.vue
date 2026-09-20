<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc4m0ib3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc4m0ib3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-podcasts-light" /></template>
