<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9jlb0bcj.css';
import '../../css/t/t-558ne9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9jlb0bcj"/><path class="t-558ne9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desert-48" /></template>
