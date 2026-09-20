<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_3-hbgnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_3-hbgnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-sharp-duotone" /></template>
