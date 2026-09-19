<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pytqn_vuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pytqn_vuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-remove-thin" /></template>
