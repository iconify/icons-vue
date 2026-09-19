<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajbs2lbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="ajbs2lbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:jcb" /></template>
