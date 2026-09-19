<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eour_gbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eour_gbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:archive-in" /></template>
