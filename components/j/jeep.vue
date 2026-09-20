<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga4go3bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga4go3bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jeep" /></template>
