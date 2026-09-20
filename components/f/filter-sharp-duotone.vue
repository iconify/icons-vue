<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wky-31b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wky-31b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-sharp-duotone" /></template>
