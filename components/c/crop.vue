<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj0mo180q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj0mo180q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:crop" /></template>
