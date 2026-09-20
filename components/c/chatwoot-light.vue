<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs3w2zbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gs3w2zbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chatwoot-light" /></template>
