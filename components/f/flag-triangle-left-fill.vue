<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5-a49vjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5-a49vjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-triangle-left-fill" /></template>
