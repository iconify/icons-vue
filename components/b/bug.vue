<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6oybf-di.css';
import '../../css/d/dh5g9c5ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z6oybf-di"/><path class="dh5g9c5ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bug" /></template>
