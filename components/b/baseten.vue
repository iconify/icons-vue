<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra_8gx4bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_8gx4bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:baseten" /></template>
