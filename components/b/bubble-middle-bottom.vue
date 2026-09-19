<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9breojos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p9breojos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-middle-bottom" /></template>
