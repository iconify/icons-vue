<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfhtnms6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfhtnms6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gimp-light" /></template>
