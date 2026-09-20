<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ej__5_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7ej__5_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:erlenmeyer-flask-solid" /></template>
