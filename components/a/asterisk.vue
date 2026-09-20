<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwo6y5lbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwo6y5lbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:asterisk" /></template>
