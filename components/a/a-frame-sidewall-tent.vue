<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqh81ubec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jqh81ubec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:a-frame-sidewall-tent" /></template>
