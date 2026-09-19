<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbnj-db8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbnj-db8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heading-h5" /></template>
