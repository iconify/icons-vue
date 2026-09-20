<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxys1wisk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxys1wisk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:effect" /></template>
