<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx20v6byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx20v6byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:home-alt-01-filled" /></template>
