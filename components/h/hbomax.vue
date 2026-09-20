<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zupls5bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zupls5bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hbomax" /></template>
