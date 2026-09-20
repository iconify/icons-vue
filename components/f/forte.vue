<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p17ncey3b.css';
import '../../css/l/lz667430k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p17ncey3b"/><path class="lz667430k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forte" /></template>
