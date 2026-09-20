<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op6a2bbfz.css';
import '../../css/s/s6z8b405g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op6a2bbfz"/><path class="s6z8b405g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:folder-open" /></template>
