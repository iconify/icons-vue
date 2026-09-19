<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duxim6xmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duxim6xmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-skull-filled" /></template>
