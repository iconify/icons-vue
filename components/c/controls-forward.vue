<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2tdnqxkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c2tdnqxkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-forward" /></template>
