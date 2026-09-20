<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4rsdhbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4rsdhbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:facebook-circle-line" /></template>
