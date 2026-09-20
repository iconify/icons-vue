<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brj83-_4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":60};
const content = `<path class="brj83-_4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:interfere-dark" /></template>
