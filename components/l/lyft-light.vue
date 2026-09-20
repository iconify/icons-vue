<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slc1jnbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="slc1jnbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lyft-light" /></template>
