<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_3n8na5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_3n8na5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockform-dark" /></template>
