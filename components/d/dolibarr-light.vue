<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0p-n6nhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0p-n6nhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dolibarr-light" /></template>
