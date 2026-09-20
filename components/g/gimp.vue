<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znv1ogblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znv1ogblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gimp" /></template>
