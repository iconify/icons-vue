<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq-l14o0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="kq-l14o0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:cloud" /></template>
