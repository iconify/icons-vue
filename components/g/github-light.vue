<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dix83fwqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dix83fwqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-light" /></template>
