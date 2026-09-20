<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qco1wwqfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qco1wwqfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:comptia" /></template>
