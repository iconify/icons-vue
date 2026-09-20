<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrhh4yzcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrhh4yzcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:battery-full" /></template>
