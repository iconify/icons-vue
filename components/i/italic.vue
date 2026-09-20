<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5-x_5z0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5-x_5z0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:italic" /></template>
