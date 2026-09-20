<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctuz6eght.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ctuz6eght"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:circle-big-filled" /></template>
