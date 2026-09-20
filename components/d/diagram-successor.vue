<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t24yx0btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t24yx0btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-successor" /></template>
