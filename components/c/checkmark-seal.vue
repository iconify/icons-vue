<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzo40-rhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hzo40-rhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-seal" /></template>
