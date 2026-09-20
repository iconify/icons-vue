<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eitxf6jcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eitxf6jcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-block" /></template>
