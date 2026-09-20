<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3tw8a-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em3tw8a-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grip-vertical-duotone" /></template>
