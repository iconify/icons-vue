<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_t6k4brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w_t6k4brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:erlenmeyer-flask-remix" /></template>
