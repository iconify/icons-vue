<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdup9ob0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdup9ob0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:lamp" /></template>
