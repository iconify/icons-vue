<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta5b9vw8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ta5b9vw8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:day-snow" /></template>
