<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8eaf2bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path clip-rule="evenodd" class="s8eaf2bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:github-light" /></template>
