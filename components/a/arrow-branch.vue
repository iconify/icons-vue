<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvp0-qsza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jvp0-qsza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-branch" /></template>
