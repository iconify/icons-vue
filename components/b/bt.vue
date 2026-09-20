<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqdrd48yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdrd48yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bt" /></template>
