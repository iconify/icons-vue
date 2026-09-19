<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5yg-621y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":999,"height":1000};
const content = `<path class="b5yg-621y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-happy" /></template>
