<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k55cu9bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k55cu9bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:loop-24" /></template>
