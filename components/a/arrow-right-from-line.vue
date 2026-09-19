<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8zkomhef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8zkomhef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-right-from-line" /></template>
