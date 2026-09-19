<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le_guxbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="le_guxbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bus" /></template>
