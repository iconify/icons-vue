<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip70a665c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ip70a665c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:configarr-dark" /></template>
