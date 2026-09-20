<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e42-bacmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e42-bacmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dandelion-line" /></template>
