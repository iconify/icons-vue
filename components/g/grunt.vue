<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ape3adbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ape3adbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:grunt" /></template>
