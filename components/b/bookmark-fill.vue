<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlmw21bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hlmw21bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bookmark-fill" /></template>
