<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcvu8dgax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcvu8dgax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-left-l" /></template>
