<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl-3szpmw.css';
import '../../css/g/g_0ul0b0z.css';
import '../../css/g/gnu88kuoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bl-3szpmw"/><path class="g_0ul0b0z"/><path class="gnu88kuoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:group" /></template>
