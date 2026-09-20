<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjyx7za2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjyx7za2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:angry-fill" /></template>
