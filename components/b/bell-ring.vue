<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcab6zgmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcab6zgmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bell-ring" /></template>
