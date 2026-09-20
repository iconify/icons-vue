<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p09a5v0qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p09a5v0qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coinmarketcap-dark" /></template>
