<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2b8b2bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2b8b2bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-right-dashed-panel-sharp-fill" /></template>
