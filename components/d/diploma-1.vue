<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k37e854ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="k37e854ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:diploma-1" /></template>
