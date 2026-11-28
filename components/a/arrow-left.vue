<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrm8teb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrm8teb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-left" /></template>
