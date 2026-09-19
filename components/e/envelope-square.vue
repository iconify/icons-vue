<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa9audbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="sa9audbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:envelope-square" /></template>
