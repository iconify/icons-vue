<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb1wavm9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb1wavm9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atlasnode-dark" /></template>
