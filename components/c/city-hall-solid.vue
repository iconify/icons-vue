<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1w3bn26c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r1w3bn26c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:city-hall-solid" /></template>
