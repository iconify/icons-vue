<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhzup7bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vhzup7bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lips" /></template>
