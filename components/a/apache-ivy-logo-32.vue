<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9wrx1xgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v9wrx1xgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:apache-ivy-logo-32" /></template>
