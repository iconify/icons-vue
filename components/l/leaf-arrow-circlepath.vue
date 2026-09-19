<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_mec57ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y_mec57ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:leaf-arrow-circlepath" /></template>
