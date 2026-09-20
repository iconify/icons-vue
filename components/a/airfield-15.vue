<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twrtzr8ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="twrtzr8ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:airfield-15" /></template>
