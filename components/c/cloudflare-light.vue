<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef4c8rz-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ef4c8rz-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudflare-light" /></template>
