<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phqysqbjw.css';
import '../../css/d/dinarbh3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="phqysqbjw"/><path class="dinarbh3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:handlebars" /></template>
