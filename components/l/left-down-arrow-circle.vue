<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj98ueone.css';
import '../../css/t/t95d9j63b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj98ueone"/><path class="t95d9j63b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:left-down-arrow-circle" /></template>
