<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgy_ef_3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bgy_ef_3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cadvisor-light" /></template>
