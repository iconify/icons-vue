<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm93pvfhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jm93pvfhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:descending" /></template>
