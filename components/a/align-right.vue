<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyj7c0ewx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyj7c0ewx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:align-right" /></template>
