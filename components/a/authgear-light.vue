<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev6_nwamt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ev6_nwamt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authgear-light" /></template>
