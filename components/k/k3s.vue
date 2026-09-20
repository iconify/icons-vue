<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jro49pouc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jro49pouc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:k3s" /></template>
