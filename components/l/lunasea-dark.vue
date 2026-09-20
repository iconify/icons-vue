<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5bb0i2_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5bb0i2_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunasea-dark" /></template>
