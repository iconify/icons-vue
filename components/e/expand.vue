<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o19u6j1mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o19u6j1mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:expand" /></template>
