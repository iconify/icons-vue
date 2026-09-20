<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k48fiacvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k48fiacvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:helium-mobile-dark" /></template>
