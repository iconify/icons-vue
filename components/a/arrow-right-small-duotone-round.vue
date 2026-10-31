<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4_hgnj9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4_hgnj9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-small-duotone-round" /></template>
