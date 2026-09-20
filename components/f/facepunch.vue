<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf1opr1rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf1opr1rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:facepunch" /></template>
