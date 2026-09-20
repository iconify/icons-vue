<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu2di8bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu2di8bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-inner-fill" /></template>
