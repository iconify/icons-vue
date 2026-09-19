<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7alt82_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y7alt82_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:horizontalcontract" /></template>
