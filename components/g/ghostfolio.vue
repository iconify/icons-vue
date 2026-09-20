<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwcuq-bwx.css';
import '../../css/d/dcwqgdbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwcuq-bwx"/><path class="dcwqgdbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghostfolio" /></template>
