<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2fxoablb.css';
import '../../css/m/mru10lbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h2fxoablb"/><path class="mru10lbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carbon" /></template>
