<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bexyg-fke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bexyg-fke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:animation-digital-network-dark" /></template>
