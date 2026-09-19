<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y48v3sbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="y48v3sbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:clipboard-check" /></template>
