<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax6l9-l3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax6l9-l3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cup-soda-solid" /></template>
