<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjije9bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="kjije9bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bower" /></template>
