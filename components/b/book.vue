<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/botcjxbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="botcjxbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:book" /></template>
