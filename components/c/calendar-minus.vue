<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4ma7zbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4ma7zbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-minus" /></template>
