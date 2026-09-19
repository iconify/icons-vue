<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3312sc7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f3312sc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope-circle" /></template>
