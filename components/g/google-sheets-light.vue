<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alabeshfc.css';
import '../../css/l/lb66l3jkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alabeshfc"/><path class="lb66l3jkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-sheets-light" /></template>
