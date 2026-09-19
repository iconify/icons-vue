<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o563r6b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o563r6b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-plus-solid" /></template>
