<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgm8q8b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="vgm8q8b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleo" /></template>
