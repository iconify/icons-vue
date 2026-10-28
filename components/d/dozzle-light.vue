<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtw5n0crk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtw5n0crk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dozzle-light" /></template>
