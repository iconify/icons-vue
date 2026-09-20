<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_y028i5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="c_y028i5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:askquestion" /></template>
