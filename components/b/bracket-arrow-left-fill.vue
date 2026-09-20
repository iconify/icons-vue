<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiwjijb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwjijb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-left-fill" /></template>
