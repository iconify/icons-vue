<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itx84tljk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itx84tljk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:last-fm" /></template>
