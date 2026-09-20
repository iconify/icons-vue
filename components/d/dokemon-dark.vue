<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbftvacto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbftvacto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dokemon-dark" /></template>
