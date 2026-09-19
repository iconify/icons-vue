<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jji2zbjkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="jji2zbjkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:checkbox-26" /></template>
