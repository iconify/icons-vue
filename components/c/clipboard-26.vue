<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufjhs5b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ufjhs5b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-26" /></template>
