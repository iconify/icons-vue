<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyj57ic1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyj57ic1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fossa" /></template>
