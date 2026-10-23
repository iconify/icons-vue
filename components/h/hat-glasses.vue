<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0up8ucko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0up8ucko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hat-glasses" /></template>
