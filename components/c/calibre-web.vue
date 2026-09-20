<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_uir6bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_uir6bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calibre-web" /></template>
