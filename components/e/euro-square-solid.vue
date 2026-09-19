<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbknc0bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbknc0bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:euro-square-solid" /></template>
