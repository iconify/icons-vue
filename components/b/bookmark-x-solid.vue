<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw9wn5d7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw9wn5d7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-x-solid" /></template>
