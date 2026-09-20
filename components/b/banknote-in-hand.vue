<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt8qhhped.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qt8qhhped"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banknote-in-hand" /></template>
