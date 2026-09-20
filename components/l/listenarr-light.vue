<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgkoy4z8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgkoy4z8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listenarr-light" /></template>
