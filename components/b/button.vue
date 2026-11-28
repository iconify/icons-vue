<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s273e8tgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s273e8tgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:button" /></template>
