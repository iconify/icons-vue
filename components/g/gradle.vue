<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpqlw8uhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpqlw8uhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gradle" /></template>
