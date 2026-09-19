<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_v3jdmza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p_v3jdmza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:justify-right" /></template>
