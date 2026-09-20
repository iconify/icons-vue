<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uujuzybax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uujuzybax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:focus-3" /></template>
