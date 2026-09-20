<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an6zuxdwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="an6zuxdwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:an-otter-wiki-light" /></template>
