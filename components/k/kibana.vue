<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwr_9_bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xwr_9_bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:kibana" /></template>
