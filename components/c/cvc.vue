<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf2se5b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qf2se5b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cvc" /></template>
