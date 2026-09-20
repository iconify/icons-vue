<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_gkd6bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_gkd6bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:advent-of-code" /></template>
