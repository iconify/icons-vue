<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oork3ibal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oork3ibal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-branch" /></template>
