<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plsk20n4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plsk20n4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-keep-dark" /></template>
