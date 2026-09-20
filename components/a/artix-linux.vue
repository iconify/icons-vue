<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrs9bx7bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrs9bx7bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:artix-linux" /></template>
