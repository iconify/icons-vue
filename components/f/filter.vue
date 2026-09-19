<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ytm8b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o9ytm8b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:filter" /></template>
