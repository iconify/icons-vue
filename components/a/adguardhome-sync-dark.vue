<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hizec3bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hizec3bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguardhome-sync-dark" /></template>
