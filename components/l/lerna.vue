<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_eo4xb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_eo4xb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lerna" /></template>
