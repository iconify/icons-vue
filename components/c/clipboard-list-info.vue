<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax5h1hb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax5h1hb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-list-info" /></template>
