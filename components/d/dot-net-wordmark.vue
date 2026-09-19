<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0cn4bty.css';
import '../../css/j/j9asqvqjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zg0cn4bty"/><path clip-rule="evenodd" class="j9asqvqjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dot-net-wordmark" /></template>
