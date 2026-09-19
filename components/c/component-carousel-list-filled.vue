<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho3y81gdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ho3y81gdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-carousel-list-filled" /></template>
