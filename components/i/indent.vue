<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcd4nhlvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcd4nhlvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:indent" /></template>
