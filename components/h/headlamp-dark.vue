<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u13imoq4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u13imoq4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headlamp-dark" /></template>
