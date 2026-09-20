<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plrm2twbs.css';
import '../../css/k/ku0zhsboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plrm2twbs"/><path class="ku0zhsboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ipvanish" /></template>
