<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa7lk71xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qa7lk71xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bug-block" /></template>
