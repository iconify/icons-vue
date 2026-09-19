<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcibvrb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcibvrb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cable-car" /></template>
