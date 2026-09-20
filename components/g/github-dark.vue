<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9mf81bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path clip-rule="evenodd" class="m9mf81bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:github-dark" /></template>
