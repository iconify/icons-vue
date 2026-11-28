<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbk-j9k3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbk-j9k3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:armchair" /></template>
