<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh0qs-btc.css';
import '../../css/d/dgnjy1a4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="lh0qs-btc"/><path class="dgnjy1a4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:easel-outline" /></template>
