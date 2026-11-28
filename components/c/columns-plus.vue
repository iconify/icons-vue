<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr0y-c_1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0y-c_1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:columns-plus" /></template>
