<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3fk4rlyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v3fk4rlyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:hunting-stand-14" /></template>
