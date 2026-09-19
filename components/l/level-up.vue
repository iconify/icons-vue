<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt4lrqb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qt4lrqb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:level-up" /></template>
