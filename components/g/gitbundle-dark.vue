<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9zf_dony.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9zf_dony"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitbundle-dark" /></template>
