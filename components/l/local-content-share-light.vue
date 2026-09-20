<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l37szz5mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l37szz5mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:local-content-share-light" /></template>
