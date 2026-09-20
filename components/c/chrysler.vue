<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhlr7h7su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhlr7h7su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chrysler" /></template>
