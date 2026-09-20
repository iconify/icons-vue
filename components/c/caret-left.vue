<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm7bv5bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm7bv5bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-left" /></template>
