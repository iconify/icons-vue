<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyk9cabui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyk9cabui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:invisible-2" /></template>
