<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djxmpsilu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="djxmpsilu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:javascript-test" /></template>
