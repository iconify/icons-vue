<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx6wbyhzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx6wbyhzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-fill" /></template>
