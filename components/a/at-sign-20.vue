<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t170-qrdh.css';
import '../../css/u/uto33fc8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t170-qrdh"/><path class="uto33fc8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:at-sign-20" /></template>
