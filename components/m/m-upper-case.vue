<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1dcbxwrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":620,"height":753};
const content = `<path class="c1dcbxwrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:m-upper-case" /></template>
