<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxjbuiruv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxjbuiruv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chatwoot-dark" /></template>
