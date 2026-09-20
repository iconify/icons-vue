<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-he2ybnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-he2ybnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:grand-frais" /></template>
