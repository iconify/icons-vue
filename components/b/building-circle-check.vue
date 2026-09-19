<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl0thdbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gl0thdbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:building-circle-check" /></template>
