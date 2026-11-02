<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m67v-61ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m67v-61ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-out-control-point-fill" /></template>
