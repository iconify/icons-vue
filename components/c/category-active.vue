<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4jf7jyqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4jf7jyqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:category-active" /></template>
