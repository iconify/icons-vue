<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm0aez-8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hm0aez-8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-straight" /></template>
