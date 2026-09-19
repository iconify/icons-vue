<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jof-b7b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jof-b7b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-arrow-left-square-fill" /></template>
