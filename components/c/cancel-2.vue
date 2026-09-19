<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcuhc8bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kcuhc8bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:cancel-2" /></template>
