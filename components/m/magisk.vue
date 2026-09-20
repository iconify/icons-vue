<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jznvnct7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jznvnct7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:magisk" /></template>
