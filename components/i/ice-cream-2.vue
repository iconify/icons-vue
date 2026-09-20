<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfsfc7bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfsfc7bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ice-cream-2" /></template>
