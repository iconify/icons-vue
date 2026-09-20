<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2p5vab0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2p5vab0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:heading-24" /></template>
