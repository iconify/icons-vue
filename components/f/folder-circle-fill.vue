<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwq9oyboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jwq9oyboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-circle-fill" /></template>
