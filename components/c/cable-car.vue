<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_z8hublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_z8hublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cable-car" /></template>
