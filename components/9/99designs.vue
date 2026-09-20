<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j37bt1bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j37bt1bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:99designs" /></template>
