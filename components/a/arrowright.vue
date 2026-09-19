<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcffhsb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":690,"height":718};
const content = `<path class="hcffhsb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:arrowright" /></template>
