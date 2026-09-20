<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsnj0do4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsnj0do4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ai2" /></template>
