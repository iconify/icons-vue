<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhjv9dbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhjv9dbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:columns" /></template>
