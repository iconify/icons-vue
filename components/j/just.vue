<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxczl7bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxczl7bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:just" /></template>
