<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei1iof_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hei1iof_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inception-labs" /></template>
