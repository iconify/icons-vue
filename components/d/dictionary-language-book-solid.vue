<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gir5-qiqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gir5-qiqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dictionary-language-book-solid" /></template>
