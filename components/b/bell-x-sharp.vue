<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqkr8dk-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqkr8dk-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-x-sharp" /></template>
