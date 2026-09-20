<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfp9bv07i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfp9bv07i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-x" /></template>
