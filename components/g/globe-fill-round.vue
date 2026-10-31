<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxpdebbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxpdebbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-fill-round" /></template>
