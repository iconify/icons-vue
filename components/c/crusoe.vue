<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4621jb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4621jb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:crusoe" /></template>
