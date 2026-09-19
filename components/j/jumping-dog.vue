<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk-jqx9ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk-jqx9ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jumping-dog" /></template>
