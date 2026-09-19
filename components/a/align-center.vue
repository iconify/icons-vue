<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk7f85f6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="jk7f85f6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:align-center" /></template>
