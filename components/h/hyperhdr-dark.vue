<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eve3a1jad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eve3a1jad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperhdr-dark" /></template>
