<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay4xc3ohy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay4xc3ohy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-question" /></template>
