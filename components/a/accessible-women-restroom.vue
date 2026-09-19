<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsyqg_0ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsyqg_0ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:accessible-women-restroom" /></template>
