<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtot7pbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtot7pbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-book-upload-fill" /></template>
