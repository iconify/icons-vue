<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m14puibhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m14puibhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-victory-fill" /></template>
