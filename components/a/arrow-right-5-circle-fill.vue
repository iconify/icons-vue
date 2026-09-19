<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bovqn3gyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bovqn3gyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-5-circle-fill" /></template>
