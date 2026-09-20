<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vymw6t_6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vymw6t_6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:boxy-svg" /></template>
