<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2yps7bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2yps7bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bookmark-circle-solid" /></template>
