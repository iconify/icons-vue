<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnvj_8bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":990,"height":1000};
const content = `<path class="hnvj_8bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-sunglasses" /></template>
