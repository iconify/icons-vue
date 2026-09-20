<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opzsjk9an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="opzsjk9an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dictionary-language-book-remix" /></template>
