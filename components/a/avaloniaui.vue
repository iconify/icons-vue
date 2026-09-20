<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjv16bcly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjv16bcly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:avaloniaui" /></template>
