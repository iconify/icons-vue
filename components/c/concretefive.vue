<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk-v_9b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":895,"height":1024};
const content = `<path class="nk-v_9b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:concretefive" /></template>
