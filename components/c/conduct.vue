<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k600kgb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k600kgb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:conduct" /></template>
