<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjcuh8_ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mjcuh8_ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:dashboard" /></template>
