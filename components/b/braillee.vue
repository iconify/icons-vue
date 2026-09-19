<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mswucdbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="mswucdbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillee" /></template>
