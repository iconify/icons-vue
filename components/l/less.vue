<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlzqv1cqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlzqv1cqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:less" /></template>
