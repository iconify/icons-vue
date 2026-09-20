<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpxlm7b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lpxlm7b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookhaven-light" /></template>
