<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/janv62ygw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="janv62ygw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:acrobat-reader" /></template>
