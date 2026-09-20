<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch0q1dbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch0q1dbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:compilerexplorer" /></template>
