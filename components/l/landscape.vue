<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukbu8n6kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ukbu8n6kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:landscape" /></template>
