<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycoe2fbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycoe2fbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-right-dashed-panel-sharp-fill" /></template>
