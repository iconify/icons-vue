<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj5k-rjmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hj5k-rjmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calibre-web" /></template>
