<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqb1-0mmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqb1-0mmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-piano" /></template>
