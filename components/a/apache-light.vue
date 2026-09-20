<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irw-9-bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irw-9-bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-light" /></template>
