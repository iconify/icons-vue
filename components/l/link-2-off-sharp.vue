<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rllvkobji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rllvkobji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link-2-off-sharp" /></template>
