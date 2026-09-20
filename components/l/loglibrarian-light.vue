<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkb3zf1ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkb3zf1ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loglibrarian-light" /></template>
