<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfi6hnbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfi6hnbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:info-square" /></template>
