<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao7i-rcqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao7i-rcqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fyle" /></template>
