<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_0aycbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_0aycbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kherad-dark" /></template>
