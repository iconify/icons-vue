<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7yq9sboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7yq9sboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:casaos-dark" /></template>
