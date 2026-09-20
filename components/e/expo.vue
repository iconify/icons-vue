<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9okd2b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9okd2b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:expo" /></template>
