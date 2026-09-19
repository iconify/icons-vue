<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go6x9hbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go6x9hbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-amazon" /></template>
