<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk8o4mlup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk8o4mlup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:door-closed" /></template>
