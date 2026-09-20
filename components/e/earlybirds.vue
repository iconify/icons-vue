<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6j-kt1ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h6j-kt1ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:earlybirds" /></template>
