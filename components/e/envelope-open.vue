<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea1rhccvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ea1rhccvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:envelope-open" /></template>
