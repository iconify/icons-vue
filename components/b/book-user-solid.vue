<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjaa4rkcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjaa4rkcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-user-solid" /></template>
