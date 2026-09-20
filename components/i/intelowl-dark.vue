<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe7x_gb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe7x_gb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intelowl-dark" /></template>
