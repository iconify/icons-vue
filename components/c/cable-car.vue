<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whkmt38hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whkmt38hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cable-car" /></template>
