<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oco-8fb8g.css';
import '../../css/t/tk-rzp94k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oco-8fb8g"/><path class="tk-rzp94k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beer" /></template>
