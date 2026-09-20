<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8o44pbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u8o44pbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hewlett-packard-enterprise-dark" /></template>
