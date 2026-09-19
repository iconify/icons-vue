<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox79-4b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ox79-4b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cow" /></template>
