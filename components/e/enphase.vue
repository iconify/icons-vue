<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gszlt-bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gszlt-bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:enphase" /></template>
