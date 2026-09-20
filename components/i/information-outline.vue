<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia6arpbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ia6arpbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:information-outline" /></template>
