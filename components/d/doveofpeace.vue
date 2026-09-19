<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2zjwor-m.css';
import '../../css/t/tc57l1bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2zjwor-m"/><path class="tc57l1bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:doveofpeace" /></template>
