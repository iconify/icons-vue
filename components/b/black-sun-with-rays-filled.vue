<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0097eb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b0097eb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-sun-with-rays-filled" /></template>
