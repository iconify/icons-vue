<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_a-9r90o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_a-9r90o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-u-turn-down-line-solid" /></template>
