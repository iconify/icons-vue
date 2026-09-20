<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1x776i8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p1x776i8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:local-content-share-dark" /></template>
