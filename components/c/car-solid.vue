<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq3sqqqnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="dq3sqqqnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:car-solid" /></template>
