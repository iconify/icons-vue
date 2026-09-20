<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tih5mtbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tih5mtbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iterm2" /></template>
