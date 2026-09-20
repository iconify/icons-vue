<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz5nuxbgv.css';
import '../../css/s/szs1rbc2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nz5nuxbgv"/><path class="szs1rbc2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lemmy" /></template>
