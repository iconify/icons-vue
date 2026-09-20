<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frjvp-1mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="frjvp-1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:box-solid" /></template>
