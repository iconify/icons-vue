<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9vvm_wmz.css';
import '../../css/z/zpxidp81t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9vvm_wmz"/><path class="zpxidp81t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-vertical-24" /></template>
