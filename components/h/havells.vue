<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gagg8eboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gagg8eboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:havells" /></template>
