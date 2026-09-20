<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/focd844dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="focd844dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dex-auth-dark" /></template>
