<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg-4ik0ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lg-4ik0ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitsave-dark" /></template>
