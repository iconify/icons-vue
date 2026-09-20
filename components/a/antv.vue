<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v81fy1bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v81fy1bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:antv" /></template>
