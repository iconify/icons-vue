<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpb_-2b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpb_-2b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inventree-light" /></template>
