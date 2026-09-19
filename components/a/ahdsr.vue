<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiaigybua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jiaigybua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:ahdsr" /></template>
