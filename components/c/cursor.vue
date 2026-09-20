<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm5nk2bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rm5nk2bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cursor" /></template>
