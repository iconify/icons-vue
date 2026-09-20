<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obw2w46mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obw2w46mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:italic-sharp-fill" /></template>
