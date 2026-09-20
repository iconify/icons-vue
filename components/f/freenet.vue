<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi_v-c7ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi_v-c7ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freenet" /></template>
