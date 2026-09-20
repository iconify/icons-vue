<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocf2bv34c.css';
import '../../css/o/ou5xg8k1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocf2bv34c"/><path class="ou5xg8k1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghostboard" /></template>
