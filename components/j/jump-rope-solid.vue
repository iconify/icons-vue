<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb4wu5xei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb4wu5xei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:jump-rope-solid" /></template>
