<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-4y4dmgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-4y4dmgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haproxy-light" /></template>
