<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9dzyiszx.css';
import '../../css/q/qz4brhaoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="qz4brhaoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-alert-20" /></template>
