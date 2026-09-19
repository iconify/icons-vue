<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egp6p36lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egp6p36lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-down-solid" /></template>
